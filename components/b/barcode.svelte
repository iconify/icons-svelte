<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3-u3ab7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="h3-u3ab7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:barcode" {...props}></Icon>
