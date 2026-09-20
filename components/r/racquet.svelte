<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl5-qvbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hl5-qvbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:racquet" {...props}></Icon>
