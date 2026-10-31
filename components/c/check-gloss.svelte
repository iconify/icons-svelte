<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh1qoo5sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh1qoo5sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:check-gloss" {...props}></Icon>
