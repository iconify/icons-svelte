<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi84fdbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi84fdbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:logs" {...props}></Icon>
