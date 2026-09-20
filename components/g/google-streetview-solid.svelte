<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxrry-bew.css';
import '../../css/q/q_k3wsbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nxrry-bew"/><path class="q_k3wsbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:google-streetview-solid" {...props}></Icon>
