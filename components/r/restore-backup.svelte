<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-lsa2wrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-lsa2wrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:restore-backup" {...props}></Icon>
