<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq74e8-al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aq74e8-al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:life-ring" {...props}></Icon>
