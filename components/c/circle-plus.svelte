<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz3k9hb8j.css';
import '../../css/y/yl2xz9yma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wz3k9hb8j"/><path class="yl2xz9yma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:circle-plus" {...props}></Icon>
