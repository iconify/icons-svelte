<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq3z2ybyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gq3z2ybyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:folders" {...props}></Icon>
