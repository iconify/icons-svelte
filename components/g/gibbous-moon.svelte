<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv02tvbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv02tvbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gibbous-moon" {...props}></Icon>
