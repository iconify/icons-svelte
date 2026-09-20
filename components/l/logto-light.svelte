<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx_-4nu-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qx_-4nu-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logto-light" {...props}></Icon>
