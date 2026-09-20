<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5r02k1wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5r02k1wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lock-checked" {...props}></Icon>
