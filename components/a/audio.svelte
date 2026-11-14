<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owtb_jhsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owtb_jhsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:audio" {...props}></Icon>
