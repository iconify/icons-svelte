<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3tol2bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3tol2bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bacon" {...props}></Icon>
