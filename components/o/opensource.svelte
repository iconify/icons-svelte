<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnki2-boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hnki2-boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:opensource" {...props}></Icon>
