<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnf51sb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnf51sb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fire-square-filled" {...props}></Icon>
