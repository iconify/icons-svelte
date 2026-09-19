<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlmg-pvsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlmg-pvsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:rice-cracker" {...props}></Icon>
