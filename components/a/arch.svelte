<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbgwtmbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cbgwtmbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arch" {...props}></Icon>
