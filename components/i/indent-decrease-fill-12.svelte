<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xadmxrn2z.css';
import '../../css/d/dssw0v5yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xadmxrn2z"/><path class="dssw0v5yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-decrease-fill-12" {...props}></Icon>
