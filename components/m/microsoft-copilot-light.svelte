<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a53r7jbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a53r7jbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-copilot-light" {...props}></Icon>
