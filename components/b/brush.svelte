<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjxhorbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1026};
const content = `<path class="hjxhorbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brush" {...props}></Icon>
