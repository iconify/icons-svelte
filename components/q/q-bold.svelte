<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukf4kubog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ukf4kubog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:q-bold" {...props}></Icon>
