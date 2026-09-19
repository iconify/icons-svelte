<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am565_bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="am565_bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:legal" {...props}></Icon>
