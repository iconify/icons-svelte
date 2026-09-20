<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaqkfbc1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaqkfbc1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paperclip-horizontal" {...props}></Icon>
