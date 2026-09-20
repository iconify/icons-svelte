<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpdtolbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpdtolbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:document-like-filled" {...props}></Icon>
