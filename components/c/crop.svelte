<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jywtkxo3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="jywtkxo3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop" {...props}></Icon>
