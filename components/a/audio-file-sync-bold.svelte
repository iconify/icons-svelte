<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mssq4ub0k.css';
import '../../css/l/lkvs5hb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mssq4ub0k"/><path class="lkvs5hb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:audio-file-sync-bold" {...props}></Icon>
