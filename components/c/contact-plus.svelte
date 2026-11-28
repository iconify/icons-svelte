<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it78czskb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it78czskb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:contact-plus" {...props}></Icon>
