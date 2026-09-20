<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3_8h7bqu.css';
import '../../css/h/h1yxmgitg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3_8h7bqu"/><path class="h1yxmgitg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:camera-1-filled" {...props}></Icon>
