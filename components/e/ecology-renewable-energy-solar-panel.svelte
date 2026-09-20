<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zknv2ormj.css';
import '../../css/v/vnc6qjvvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zknv2ormj"/><path class="vnc6qjvvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-renewable-energy-solar-panel" {...props}></Icon>
