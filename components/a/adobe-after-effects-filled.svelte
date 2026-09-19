<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg2_fzpty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lg2_fzpty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-after-effects-filled" {...props}></Icon>
