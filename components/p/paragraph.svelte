<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4o6ss61z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4o6ss61z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:paragraph" {...props}></Icon>
