<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjdn7rc0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fjdn7rc0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:comment-bubble" {...props}></Icon>
