<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whnx72bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whnx72bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:controls-forward" {...props}></Icon>
