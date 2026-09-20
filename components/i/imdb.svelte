<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zomq8mbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zomq8mbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:imdb" {...props}></Icon>
