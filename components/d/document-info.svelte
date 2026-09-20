<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abg_9_bhy.css';
import '../../css/j/j6q_paczc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abg_9_bhy"/><path clip-rule="evenodd" class="j6q_paczc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-info" {...props}></Icon>
