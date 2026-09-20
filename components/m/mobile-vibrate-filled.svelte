<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjk9j1bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjk9j1bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mobile-vibrate-filled" {...props}></Icon>
