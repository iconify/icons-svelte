<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl_d6ch4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl_d6ch4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hanger2-filled" {...props}></Icon>
