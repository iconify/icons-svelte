<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0_pw2gph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0_pw2gph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square-share" {...props}></Icon>
