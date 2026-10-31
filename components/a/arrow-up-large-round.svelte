<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhv2vsb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhv2vsb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-large-round" {...props}></Icon>
