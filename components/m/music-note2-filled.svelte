<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a423-p5qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a423-p5qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note2-filled" {...props}></Icon>
