<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj25hbbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj25hbbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:direction-dot-fill" {...props}></Icon>
