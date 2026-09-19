<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1ybyoq8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="s1ybyoq8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:adn" {...props}></Icon>
