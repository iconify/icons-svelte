<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9g86ihie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9g86ihie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:basket" {...props}></Icon>
