<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdhep31tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdhep31tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:paragraph-3" {...props}></Icon>
