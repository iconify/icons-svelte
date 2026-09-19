<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcppewgpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcppewgpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:caret-right-square" {...props}></Icon>
