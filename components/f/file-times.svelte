<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjab7rm6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjab7rm6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-times" {...props}></Icon>
