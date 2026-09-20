<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8sja11us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8sja11us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:notepad-text-dashed" {...props}></Icon>
