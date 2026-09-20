<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhpoqqbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nhpoqqbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:info-filled" {...props}></Icon>
