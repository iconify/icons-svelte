<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efbw3gbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="efbw3gbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:circle-half" {...props}></Icon>
