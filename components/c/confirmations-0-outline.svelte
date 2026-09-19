<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl48nf4cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl48nf4cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-0-outline" {...props}></Icon>
