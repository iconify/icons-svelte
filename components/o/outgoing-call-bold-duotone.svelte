<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx1qmxb2o.css';
import '../../css/j/j05r12o9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx1qmxb2o"/><path class="j05r12o9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:outgoing-call-bold-duotone" {...props}></Icon>
