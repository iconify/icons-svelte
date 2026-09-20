<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu23jnb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="iu23jnb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:lodging-11" {...props}></Icon>
