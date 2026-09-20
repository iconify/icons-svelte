<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5tvhacpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5tvhacpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diary-line" {...props}></Icon>
