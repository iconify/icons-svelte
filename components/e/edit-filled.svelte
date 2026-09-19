<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5xymnzul.css';
import '../../css/y/y1nb_hosg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5xymnzul"/><path class="y1nb_hosg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:edit-filled" {...props}></Icon>
