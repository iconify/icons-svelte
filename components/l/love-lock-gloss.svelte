<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twlfkb87e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twlfkb87e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:love-lock-gloss" {...props}></Icon>
