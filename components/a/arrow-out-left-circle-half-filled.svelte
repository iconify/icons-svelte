<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo07tbb9o.css';
import '../../css/j/jgmlxzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo07tbb9o"/><path class="jgmlxzbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-left-circle-half-filled" {...props}></Icon>
