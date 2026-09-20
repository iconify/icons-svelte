<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh_l-jx2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fh_l-jx2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-qr-remix" {...props}></Icon>
