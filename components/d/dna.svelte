<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df7su4w-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="df7su4w-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dna" {...props}></Icon>
