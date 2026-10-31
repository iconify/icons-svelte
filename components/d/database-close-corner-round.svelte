<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nie65yftb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nie65yftb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-close-corner-round" {...props}></Icon>
