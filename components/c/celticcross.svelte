<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0zjfm6yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l0zjfm6yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:celticcross" {...props}></Icon>
