<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elzab3b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="elzab3b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:maxcdn" {...props}></Icon>
