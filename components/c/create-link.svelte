<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf8cllhgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yf8cllhgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:create-link" {...props}></Icon>
