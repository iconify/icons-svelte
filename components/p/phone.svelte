<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jumt6zbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jumt6zbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:phone" {...props}></Icon>
