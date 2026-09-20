<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcarc1g3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gcarc1g3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:2-plus" {...props}></Icon>
