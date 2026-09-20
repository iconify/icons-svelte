<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k685z7nro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k685z7nro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-with-greek-cross" {...props}></Icon>
