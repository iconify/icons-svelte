<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcssw9n5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcssw9n5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-off-outline" {...props}></Icon>
