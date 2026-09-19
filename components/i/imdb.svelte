<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wordb69qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wordb69qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:imdb" {...props}></Icon>
