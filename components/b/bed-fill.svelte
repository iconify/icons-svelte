<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9_yt-30p.css';
import '../../css/p/pexua2j3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s9_yt-30p"/><path clip-rule="evenodd" class="pexua2j3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bed-fill" {...props}></Icon>
