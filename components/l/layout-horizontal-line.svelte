<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl-htwbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl-htwbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-horizontal-line" {...props}></Icon>
