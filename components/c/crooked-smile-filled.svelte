<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jux4gdbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jux4gdbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:crooked-smile-filled" {...props}></Icon>
