<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz21dlb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rz21dlb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:or" {...props}></Icon>
