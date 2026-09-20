<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq8vs9blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq8vs9blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bath" {...props}></Icon>
