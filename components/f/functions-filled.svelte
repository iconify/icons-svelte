<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efru-76vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efru-76vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:functions-filled" {...props}></Icon>
