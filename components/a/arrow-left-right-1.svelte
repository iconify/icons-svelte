<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyj4s-pbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyj4s-pbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-right-1" {...props}></Icon>
