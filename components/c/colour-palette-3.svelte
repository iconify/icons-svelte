<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uynwflb5l.css';
import '../../css/f/f-ypa7iae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="uynwflb5l"/><path clip-rule="evenodd" class="f-ypa7iae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:colour-palette-3" {...props}></Icon>
