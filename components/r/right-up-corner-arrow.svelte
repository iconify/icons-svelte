<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5otwybuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t5otwybuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:right-up-corner-arrow" {...props}></Icon>
