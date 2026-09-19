<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja0nf1bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ja0nf1bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:brackets-vertical" {...props}></Icon>
