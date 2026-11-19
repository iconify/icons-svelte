<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zujux2bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zujux2bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:infisical-light" {...props}></Icon>
