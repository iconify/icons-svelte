<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcat1lb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kcat1lb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bydesign" {...props}></Icon>
