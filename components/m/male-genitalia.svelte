<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boa45ibjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="boa45ibjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:male-genitalia" {...props}></Icon>
