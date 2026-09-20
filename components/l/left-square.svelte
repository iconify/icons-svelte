<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmdwiz__s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wmdwiz__s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:left-square" {...props}></Icon>
