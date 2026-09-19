<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jixlgacnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jixlgacnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-left" {...props}></Icon>
