<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzqznfbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqznfbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chat-add" {...props}></Icon>
