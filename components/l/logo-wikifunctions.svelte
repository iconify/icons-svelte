<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6v83qbqk.css';
import '../../css/c/c1ks9gyit.css';
import '../../css/a/azcv31byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6v83qbqk"/><path class="c1ks9gyit"/><path class="azcv31byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikifunctions" {...props}></Icon>
