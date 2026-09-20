<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-qpzbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qq-qpzbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:adjust-solid" {...props}></Icon>
