<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsze17b6g.css';
import '../../css/k/kgy_1447z.css';
import '../../css/i/i3ixtobot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gsze17b6g"><path class="kgy_1447z"/><path class="i3ixtobot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nebius" {...props}></Icon>
