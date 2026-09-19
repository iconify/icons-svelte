<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc9ys4ivd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wc9ys4ivd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:notebook-and-pen" {...props}></Icon>
