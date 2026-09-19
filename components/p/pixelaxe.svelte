<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fda2rlb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fda2rlb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelaxe" {...props}></Icon>
