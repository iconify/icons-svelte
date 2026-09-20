<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_90m36fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_90m36fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:play-chart-filled" {...props}></Icon>
