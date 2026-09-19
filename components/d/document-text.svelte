<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijh__bcqo.css';
import '../../css/j/jleau3b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ijh__bcqo"/><path class="jleau3b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:document-text" {...props}></Icon>
