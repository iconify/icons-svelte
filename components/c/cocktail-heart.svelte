<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8xv1-a3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8xv1-a3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cocktail-heart" {...props}></Icon>
