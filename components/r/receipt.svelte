<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cajek1mxb.css';
import '../../css/y/yjjqxcmso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cajek1mxb"/><path class="yjjqxcmso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:receipt" {...props}></Icon>
