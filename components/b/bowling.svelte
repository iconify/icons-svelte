<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erkfetblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="erkfetblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bowling" {...props}></Icon>
