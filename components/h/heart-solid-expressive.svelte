<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvkzxcclg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvkzxcclg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:heart-solid-expressive" {...props}></Icon>
