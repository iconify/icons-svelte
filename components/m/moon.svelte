<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xycz9duzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xycz9duzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:moon" {...props}></Icon>
