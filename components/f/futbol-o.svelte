<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3mszq0-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="x3mszq0-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:futbol-o" {...props}></Icon>
