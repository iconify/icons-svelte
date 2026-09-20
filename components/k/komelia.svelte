<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usv905b_v.css';
import '../../css/t/tnhvtrfme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="usv905b_v"/><path class="tnhvtrfme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komelia" {...props}></Icon>
