<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfo0o6wea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfo0o6wea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:broken-pottery" {...props}></Icon>
