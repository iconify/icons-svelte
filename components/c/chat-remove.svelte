<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek4jopj1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek4jopj1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chat-remove" {...props}></Icon>
