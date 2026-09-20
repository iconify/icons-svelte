<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd35nvbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="qd35nvbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:kayaking" {...props}></Icon>
