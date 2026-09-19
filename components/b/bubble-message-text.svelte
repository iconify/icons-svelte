<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azp3wpbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="azp3wpbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bubble-message-text" {...props}></Icon>
