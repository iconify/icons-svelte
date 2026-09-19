<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgl2kc_3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mgl2kc_3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:girl" {...props}></Icon>
