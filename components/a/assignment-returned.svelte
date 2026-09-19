<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2i48dbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="t2i48dbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:assignment-returned" {...props}></Icon>
