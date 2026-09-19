<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp7lv3bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mp7lv3bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:five-duo" {...props}></Icon>
