<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x57s-vb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x57s-vb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bist" {...props}></Icon>
