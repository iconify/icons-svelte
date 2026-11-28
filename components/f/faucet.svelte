<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usipjj-vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usipjj-vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:faucet" {...props}></Icon>
