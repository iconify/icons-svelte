<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwapst6yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwapst6yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:pinwheel-line" {...props}></Icon>
