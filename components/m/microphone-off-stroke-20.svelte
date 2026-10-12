<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4-hwxpky.css';
import '../../css/w/wtf96pb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c4-hwxpky"/><path class="wtf96pb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:microphone-off-stroke-20" {...props}></Icon>
