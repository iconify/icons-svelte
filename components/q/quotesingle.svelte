<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7f_7yuah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":94,"height":723};
const content = `<path class="r7f_7yuah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:quotesingle" {...props}></Icon>
