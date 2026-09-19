<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb_3d7atl.css';
import '../../css/m/mtfesl_yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mb_3d7atl"/><path class="mtfesl_yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-mic" {...props}></Icon>
