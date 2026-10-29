<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl6ew7bys.css';
import '../../css/d/dt926jbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl6ew7bys wm-k"/><path class="dt926jbqr wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:reply" {...props}></Icon>
