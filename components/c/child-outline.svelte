<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g96vl6bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g96vl6bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:child-outline" {...props}></Icon>
