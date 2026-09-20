<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg0rhxb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tg0rhxb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:classical-building-with-clock" {...props}></Icon>
