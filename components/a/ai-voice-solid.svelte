<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am0aambzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am0aambzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-voice-solid" {...props}></Icon>
