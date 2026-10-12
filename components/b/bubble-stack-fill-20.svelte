<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzk3ruo3u.css';
import '../../css/y/ybw6xbfmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rzk3ruo3u"/><path class="ybw6xbfmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-stack-fill-20" {...props}></Icon>
