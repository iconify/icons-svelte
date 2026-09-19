<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtwyitx-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":384};
const content = `<path class="rtwyitx-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-list-bulleted" {...props}></Icon>
