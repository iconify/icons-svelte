<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb6qmqbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vb6qmqbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:crop-solid" {...props}></Icon>
