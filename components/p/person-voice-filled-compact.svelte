<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqvpvccbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xqvpvccbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:person-voice-filled-compact" {...props}></Icon>
