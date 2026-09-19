<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2xsgrbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2xsgrbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:life-ring" {...props}></Icon>
