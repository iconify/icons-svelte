<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt3xbuark.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt3xbuark"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-6" {...props}></Icon>
