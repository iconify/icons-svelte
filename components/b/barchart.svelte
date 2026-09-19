<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy2302llc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dy2302llc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:barchart" {...props}></Icon>
