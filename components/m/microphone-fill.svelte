<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsz94vn-b.css';
import '../../css/k/kvf4_8b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsz94vn-b"/><path class="kvf4_8b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:microphone-fill" {...props}></Icon>
