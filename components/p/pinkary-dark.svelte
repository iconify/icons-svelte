<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjys1kbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fjys1kbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinkary-dark" {...props}></Icon>
