<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he_ivqbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="he_ivqbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:facebook" {...props}></Icon>
