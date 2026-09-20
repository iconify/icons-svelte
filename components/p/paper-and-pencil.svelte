<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3t_iyber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h3t_iyber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:paper-and-pencil" {...props}></Icon>
