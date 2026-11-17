<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt2iis1fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1084,"height":1074};
const content = `<path class="kt2iis1fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:accountantos-light" {...props}></Icon>
