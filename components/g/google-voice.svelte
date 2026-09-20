<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__ikjbpe.css';
import '../../css/u/u53z4igoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q__ikjbpe"/><path class="u53z4igoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-voice" {...props}></Icon>
