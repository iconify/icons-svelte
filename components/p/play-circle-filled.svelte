<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdu_b2b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdu_b2b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:play-circle-filled" {...props}></Icon>
