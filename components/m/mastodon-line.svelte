<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z24vtqbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z24vtqbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mastodon-line" {...props}></Icon>
