<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv_0qibyt.css';
import '../../css/y/yi-zn1bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv_0qibyt"/><path class="yi-zn1bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:icecream" {...props}></Icon>
