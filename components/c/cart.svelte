<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk67_kb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk67_kb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cart" {...props}></Icon>
