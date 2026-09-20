<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy6sd3bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="uy6sd3bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:fan" {...props}></Icon>
