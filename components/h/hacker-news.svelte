<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d55d938rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d55d938rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hacker-news" {...props}></Icon>
