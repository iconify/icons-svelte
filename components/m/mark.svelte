<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkt6a0beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dkt6a0beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:mark" {...props}></Icon>
