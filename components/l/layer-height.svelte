<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bst88j9io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bst88j9io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-height" {...props}></Icon>
