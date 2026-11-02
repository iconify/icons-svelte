<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo04cbcdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo04cbcdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bill-2-line" {...props}></Icon>
