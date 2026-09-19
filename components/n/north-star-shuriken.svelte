<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4z9n5bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k4z9n5bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:north-star-shuriken" {...props}></Icon>
