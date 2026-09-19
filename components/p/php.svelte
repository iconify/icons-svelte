<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk7j_6b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rk7j_6b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:php" {...props}></Icon>
