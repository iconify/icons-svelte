<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irr05cczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="irr05cczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dhammajak-solid" {...props}></Icon>
