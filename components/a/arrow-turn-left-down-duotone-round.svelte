<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmg_jib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmg_jib4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-left-down-duotone-round" {...props}></Icon>
