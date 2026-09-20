<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_8855w1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_8855w1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-6-1" {...props}></Icon>
