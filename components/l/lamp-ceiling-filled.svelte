<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv8m1fbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv8m1fbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lamp-ceiling-filled" {...props}></Icon>
