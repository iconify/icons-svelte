<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qerqc_trz.css';
import '../../css/g/g3fxfcd6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="qerqc_trz"/><path class="g3fxfcd6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:classification" {...props}></Icon>
