<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikbli29vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikbli29vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:flutter" {...props}></Icon>
