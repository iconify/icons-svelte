<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh2n6ee8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rh2n6ee8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bathroom" {...props}></Icon>
