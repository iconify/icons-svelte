<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au2dbgp3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au2dbgp3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:kakao-talk-line" {...props}></Icon>
