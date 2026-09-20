<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw3haybgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gw3haybgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bluetooth" {...props}></Icon>
