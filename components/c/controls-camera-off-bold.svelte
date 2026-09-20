<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn_ovn4eq.css';
import '../../css/j/jm-sdob1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn_ovn4eq"/><path class="jm-sdob1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:controls-camera-off-bold" {...props}></Icon>
