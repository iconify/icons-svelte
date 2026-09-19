<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd3llo6lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":782};
const content = `<path class="dd3llo6lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:9" {...props}></Icon>
