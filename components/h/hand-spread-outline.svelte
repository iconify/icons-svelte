<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sshpvtb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sshpvtb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-spread-outline" {...props}></Icon>
