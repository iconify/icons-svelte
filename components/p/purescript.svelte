<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_pjqt0-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q_pjqt0-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:purescript" {...props}></Icon>
