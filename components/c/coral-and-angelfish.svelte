<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-t8_bbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c-t8_bbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coral-and-angelfish" {...props}></Icon>
