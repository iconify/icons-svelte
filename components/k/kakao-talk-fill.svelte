<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xglfi1bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xglfi1bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:kakao-talk-fill" {...props}></Icon>
