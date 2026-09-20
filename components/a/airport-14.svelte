<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aje9uebwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="aje9uebwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:airport-14" {...props}></Icon>
