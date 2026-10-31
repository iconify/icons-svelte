<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjgp20b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pjgp20b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-building-with-chimney" {...props}></Icon>
