<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4eaeeb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4eaeeb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:incognito-filled" {...props}></Icon>
