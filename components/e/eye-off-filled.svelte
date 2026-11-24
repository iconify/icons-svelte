<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxg95ybdy.css';
import '../../css/k/kr-f3xbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxg95ybdy"/><path class="kr-f3xbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:eye-off-filled" {...props}></Icon>
