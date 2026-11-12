<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__ikjbpe.css';
import '../../css/z/z9e9gnbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q__ikjbpe"/><path class="z9e9gnbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-voice" {...props}></Icon>
