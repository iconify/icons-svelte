<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjyxj_bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xjyxj_bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkboxes-empty" {...props}></Icon>
