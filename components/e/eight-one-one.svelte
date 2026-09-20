<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl6az0olz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nl6az0olz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eight-one-one" {...props}></Icon>
