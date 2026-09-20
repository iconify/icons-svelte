<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsy3wcbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsy3wcbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bad-laugh-filled" {...props}></Icon>
