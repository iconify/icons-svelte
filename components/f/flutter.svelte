<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj235hbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj235hbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:flutter" {...props}></Icon>
