<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beg_1obvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="beg_1obvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:project-server-filled" {...props}></Icon>
