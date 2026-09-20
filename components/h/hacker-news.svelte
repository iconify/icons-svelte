<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a42oku2cl.css';
import '../../css/y/ytr1p0b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a42oku2cl"/><path class="ytr1p0b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hacker-news" {...props}></Icon>
