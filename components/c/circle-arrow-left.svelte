<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdx-_oc4k.css';
import '../../css/r/rf06sdq9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdx-_oc4k wm-k"/><path class="rf06sdq9n wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle-arrow-left" {...props}></Icon>
