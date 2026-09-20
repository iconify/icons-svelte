<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bms8p0b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bms8p0b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-1-filled" {...props}></Icon>
