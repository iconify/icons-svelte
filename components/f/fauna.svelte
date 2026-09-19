<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck65vcc4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":512};
const content = `<path class="ck65vcc4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fauna" {...props}></Icon>
