<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmxn7fbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmxn7fbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kitchenowl-dark" {...props}></Icon>
