<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muy_t5bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="muy_t5bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battered-axe" {...props}></Icon>
