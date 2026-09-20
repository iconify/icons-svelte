<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1fzc2bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1fzc2bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:darwinia" {...props}></Icon>
