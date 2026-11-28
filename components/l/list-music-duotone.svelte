<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-fzfcpkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-fzfcpkq primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-music-duotone" {...props}></Icon>
