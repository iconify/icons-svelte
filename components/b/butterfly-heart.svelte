<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5je0-4fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5je0-4fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:butterfly-heart" {...props}></Icon>
