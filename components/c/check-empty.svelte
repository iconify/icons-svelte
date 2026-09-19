<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhjjpdbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vhjjpdbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:check-empty" {...props}></Icon>
