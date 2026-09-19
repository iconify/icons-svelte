<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppty-ybvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":961};
const content = `<path class="ppty-ybvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lighton" {...props}></Icon>
