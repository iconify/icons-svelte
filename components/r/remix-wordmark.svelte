<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plr8h7rnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="plr8h7rnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:remix-wordmark" {...props}></Icon>
