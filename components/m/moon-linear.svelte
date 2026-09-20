<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjc34rbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjc34rbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-linear" {...props}></Icon>
