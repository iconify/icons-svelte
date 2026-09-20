<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orckkf5mu.css';
import '../../css/u/uiwntpvlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orckkf5mu"/><path class="uiwntpvlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:garlic-filled" {...props}></Icon>
