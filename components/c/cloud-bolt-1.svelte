<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii82hnrhg.css';
import '../../css/y/y0rh9nbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ii82hnrhg"/><path clip-rule="evenodd" class="y0rh9nbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-bolt-1" {...props}></Icon>
