<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j58xd_syr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j58xd_syr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:openid" {...props}></Icon>
