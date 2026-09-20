<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvmb3acso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cvmb3acso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chain-step" {...props}></Icon>
