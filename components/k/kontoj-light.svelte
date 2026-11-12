<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8745cjvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8745cjvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kontoj-light" {...props}></Icon>
