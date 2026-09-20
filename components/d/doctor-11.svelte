<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2zrc-bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="w2zrc-bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:doctor-11" {...props}></Icon>
