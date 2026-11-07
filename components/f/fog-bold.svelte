<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je8y-zlbu.css';
import '../../css/p/p2qbusfri.css';
import '../../css/f/fcdqs1q8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je8y-zlbu"/><path class="p2qbusfri"/><path class="fcdqs1q8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fog-bold" {...props}></Icon>
