<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjim-cb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yjim-cb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-voice-duotone" {...props}></Icon>
