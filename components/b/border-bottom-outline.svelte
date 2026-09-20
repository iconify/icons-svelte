<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0ch54b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f0ch54b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-bottom-outline" {...props}></Icon>
