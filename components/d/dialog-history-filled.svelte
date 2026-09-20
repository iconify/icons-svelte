<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phn7wxb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phn7wxb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dialog-history-filled" {...props}></Icon>
