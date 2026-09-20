<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsrkrvcpu.css';
import '../../css/u/uv8ih1bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsrkrvcpu"/><path class="uv8ih1bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:graph-stats-circle-bold" {...props}></Icon>
