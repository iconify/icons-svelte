<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af0yy_bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="af0yy_bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fire-ray" {...props}></Icon>
