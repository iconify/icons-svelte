<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rme7j1bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="rme7j1bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:adn" {...props}></Icon>
