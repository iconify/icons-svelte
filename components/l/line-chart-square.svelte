<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoubbo_e.css';
import '../../css/a/aydz6gbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoubbo_e"/><path class="aydz6gbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:line-chart-square" {...props}></Icon>
