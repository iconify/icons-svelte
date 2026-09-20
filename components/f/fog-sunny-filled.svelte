<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeqejkldq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeqejkldq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fog-sunny-filled" {...props}></Icon>
