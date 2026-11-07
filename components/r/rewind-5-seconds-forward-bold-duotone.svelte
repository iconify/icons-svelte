<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gekq4yo7t.css';
import '../../css/m/m87qi3nmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gekq4yo7t"/><path clip-rule="evenodd" class="m87qi3nmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-5-seconds-forward-bold-duotone" {...props}></Icon>
