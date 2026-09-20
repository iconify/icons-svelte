<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_22pptrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_22pptrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-circle-3-filled" {...props}></Icon>
