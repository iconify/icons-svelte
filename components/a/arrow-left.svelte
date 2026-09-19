<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th6h8b04z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="th6h8b04z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:arrow-left" {...props}></Icon>
