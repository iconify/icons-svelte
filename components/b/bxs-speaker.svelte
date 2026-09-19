<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz9ucbcni.css';
import '../../css/j/j6-b0layc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="wz9ucbcni"/><path class="j6-b0layc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-speaker" {...props}></Icon>
