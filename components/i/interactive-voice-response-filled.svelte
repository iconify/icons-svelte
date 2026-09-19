<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za8a9ld3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="za8a9ld3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:interactive-voice-response-filled" {...props}></Icon>
