<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d30o7nb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d30o7nb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:off" {...props}></Icon>
