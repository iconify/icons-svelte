<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt-79abhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vt-79abhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:dice-f" {...props}></Icon>
