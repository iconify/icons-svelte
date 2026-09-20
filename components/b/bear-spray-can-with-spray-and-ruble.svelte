<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0la11bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c0la11bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray-and-ruble" {...props}></Icon>
