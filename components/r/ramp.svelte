<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl9i5p93o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":69.5,"height":59};
const content = `<path class="xl9i5p93o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ramp" {...props}></Icon>
