<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3gwl8b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w3gwl8b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:laravel-wordmark" {...props}></Icon>
