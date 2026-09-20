<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxrkdqbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fxrkdqbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-baht" {...props}></Icon>
