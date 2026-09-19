<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ursm7abnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ursm7abnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyboard-filled" {...props}></Icon>
