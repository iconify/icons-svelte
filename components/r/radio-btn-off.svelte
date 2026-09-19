<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdyo0kb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wdyo0kb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:radio-btn-off" {...props}></Icon>
