<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrzcqsb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrzcqsb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bomb3-filled" {...props}></Icon>
