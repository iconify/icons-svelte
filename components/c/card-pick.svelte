<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afw2xcz8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="afw2xcz8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-pick" {...props}></Icon>
