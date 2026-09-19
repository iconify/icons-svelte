<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiskk2quo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xiskk2quo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:flutter" {...props}></Icon>
