<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk5nofhuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rk5nofhuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pizza" {...props}></Icon>
