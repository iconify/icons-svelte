<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg67gqb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rg67gqb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:raspberry-pi" {...props}></Icon>
