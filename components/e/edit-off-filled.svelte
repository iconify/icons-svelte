<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8-qqyp8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8-qqyp8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:edit-off-filled" {...props}></Icon>
