<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmi9_q11s.css';
import '../../css/j/jut9e4-pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmi9_q11s"/><path clip-rule="evenodd" class="jut9e4-pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-send-bold" {...props}></Icon>
