<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si0c0nhwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="si0c0nhwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:music" {...props}></Icon>
