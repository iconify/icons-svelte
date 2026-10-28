<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja9e3kqrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja9e3kqrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:log-out" {...props}></Icon>
