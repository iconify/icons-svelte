<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug6f-tjsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug6f-tjsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:comment-error" {...props}></Icon>
