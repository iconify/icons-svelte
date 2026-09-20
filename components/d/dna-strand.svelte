<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i85w_xbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i85w_xbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber-color:dna-strand" {...props}></Icon>
