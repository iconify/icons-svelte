<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmjdz1bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xmjdz1bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:double-chevron-start-ltr" {...props}></Icon>
