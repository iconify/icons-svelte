<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykvyq4wpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykvyq4wpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-minus-in" {...props}></Icon>
