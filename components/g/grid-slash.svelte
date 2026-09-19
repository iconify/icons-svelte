<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu24de9vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hu24de9vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:grid-slash" {...props}></Icon>
