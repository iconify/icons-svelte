<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qph61-bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qph61-bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-building-with-chimney-and-window" {...props}></Icon>
