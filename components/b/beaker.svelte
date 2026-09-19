<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmicgkb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmicgkb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:beaker" {...props}></Icon>
