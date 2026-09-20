<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahba87blp.css';
import '../../css/v/vmcevybnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahba87blp"/><path class="vmcevybnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inexogy" {...props}></Icon>
