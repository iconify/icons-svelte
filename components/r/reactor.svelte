<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rex-s-bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rex-s-bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:reactor" {...props}></Icon>
