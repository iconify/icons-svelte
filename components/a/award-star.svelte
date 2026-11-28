<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfml255xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfml255xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:award-star" {...props}></Icon>
