<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dawrykb_t.css';
import '../../css/s/srztgmmzo.css';
import '../../css/u/ugkergbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dawrykb_t"/><path class="srztgmmzo"/><path class="ugkergbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:media-protection-shield" {...props}></Icon>
