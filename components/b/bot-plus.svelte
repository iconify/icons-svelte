<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa6fe6usc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa6fe6usc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bot-plus" {...props}></Icon>
