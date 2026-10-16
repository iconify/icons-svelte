<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce70qkbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce70qkbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:alarm-multiple-filled" {...props}></Icon>
