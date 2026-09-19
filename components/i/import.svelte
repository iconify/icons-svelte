<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roweh2vhe.css';
import '../../css/q/qq-quxyif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roweh2vhe"/><path class="qq-quxyif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:import" {...props}></Icon>
