<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn39dyf6b.css';
import '../../css/j/jpc-28bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn39dyf6b"/><path class="jpc-28bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-zip-filled" {...props}></Icon>
