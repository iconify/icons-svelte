<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vckfm4x5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vckfm4x5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:contact" {...props}></Icon>
