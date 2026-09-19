<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqq-_hb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="hqq-_hb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mediarepeat" {...props}></Icon>
