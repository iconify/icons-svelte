<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i50ucibha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i50ucibha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-moon-solid" {...props}></Icon>
