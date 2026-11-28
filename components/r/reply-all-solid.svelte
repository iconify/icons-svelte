<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u34groiwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u34groiwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:reply-all-solid" {...props}></Icon>
