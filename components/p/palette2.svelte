<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr9_a__7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr9_a__7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:palette2" {...props}></Icon>
