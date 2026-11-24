<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yismpnbbv.css';
import '../../css/s/sqh8rebfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path clip-rule="evenodd" class="sqh8rebfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bot-plus-filled" {...props}></Icon>
