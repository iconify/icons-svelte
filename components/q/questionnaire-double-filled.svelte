<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0z3i-1xz.css';
import '../../css/k/kj2p-acws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0z3i-1xz"/><path class="kj2p-acws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:questionnaire-double-filled" {...props}></Icon>
