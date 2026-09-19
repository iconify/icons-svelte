<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfo7nws-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":348,"height":719};
const content = `<path class="dfo7nws-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:asterisk" {...props}></Icon>
