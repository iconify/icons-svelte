<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5mnzse4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d5mnzse4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:closed-caption" {...props}></Icon>
