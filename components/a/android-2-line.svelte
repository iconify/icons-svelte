<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kno2i6eul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kno2i6eul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:android-2-line" {...props}></Icon>
