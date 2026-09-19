<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0d_fibqc.css';
import '../../css/j/jgmlxzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0d_fibqc"/><path class="jgmlxzbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-right-circle-half-filled" {...props}></Icon>
