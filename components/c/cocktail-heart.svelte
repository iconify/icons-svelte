<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnt9jgwzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnt9jgwzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cocktail-heart" {...props}></Icon>
