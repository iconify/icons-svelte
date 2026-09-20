<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adn0iybjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adn0iybjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backrest-light" {...props}></Icon>
