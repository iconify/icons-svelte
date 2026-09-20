<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmuk06bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pmuk06bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:heart" {...props}></Icon>
