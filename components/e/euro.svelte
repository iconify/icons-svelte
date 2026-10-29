<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ohoulew.css';
import '../../css/r/ro2kipt4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9ohoulew wm-k"/><path class="ro2kipt4k wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:euro" {...props}></Icon>
