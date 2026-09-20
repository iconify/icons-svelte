<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd4ttjned.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd4ttjned"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rocket-filled" {...props}></Icon>
