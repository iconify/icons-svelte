<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a92_184ww.css';
import '../../css/m/miymqckna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a92_184ww"/><path class="miymqckna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:qr-code-filled" {...props}></Icon>
