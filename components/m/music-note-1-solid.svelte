<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv0j12bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tv0j12bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:music-note-1-solid" {...props}></Icon>
