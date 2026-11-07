<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_p9czbut.css';
import '../../css/x/xnfkpachl.css';
import '../../css/f/fvspzabcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_p9czbut"/><path class="xnfkpachl"/><path class="fvspzabcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-4-bold-duotone" {...props}></Icon>
