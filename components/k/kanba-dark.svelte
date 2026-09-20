<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z441hubzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z441hubzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kanba-dark" {...props}></Icon>
