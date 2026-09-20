<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic9catbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic9catbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:github-face" {...props}></Icon>
