<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daobr4a-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="daobr4a-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:exclamation-circle" {...props}></Icon>
