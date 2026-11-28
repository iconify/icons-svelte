<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp74bbcgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp74bbcgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ribbon-star-solid" {...props}></Icon>
