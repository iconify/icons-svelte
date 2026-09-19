<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad31_4b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ad31_4b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rosette" {...props}></Icon>
