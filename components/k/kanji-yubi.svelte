<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2mpnnbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1824,"height":1824};
const content = `<path class="v2mpnnbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:kanji-yubi" {...props}></Icon>
