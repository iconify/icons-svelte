<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjmxtcbsh.css';
import '../../css/f/f4-u1zbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjmxtcbsh"/><path class="f4-u1zbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-minus-corner-filled" {...props}></Icon>
