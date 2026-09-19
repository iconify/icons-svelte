<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcl56kzgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcl56kzgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:infinite" {...props}></Icon>
