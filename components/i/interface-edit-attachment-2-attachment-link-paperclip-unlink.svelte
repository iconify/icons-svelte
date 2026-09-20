<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqbn7bbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kqbn7bbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-attachment-2-attachment-link-paperclip-unlink" {...props}></Icon>
