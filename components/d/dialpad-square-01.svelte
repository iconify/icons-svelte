<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afu0z20lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afu0z20lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dialpad-square-01" {...props}></Icon>
