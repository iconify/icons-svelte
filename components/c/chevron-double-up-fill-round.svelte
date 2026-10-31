<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v--1l_lzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v--1l_lzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-double-up-fill-round" {...props}></Icon>
