<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj403_b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cj403_b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:piggy" {...props}></Icon>
