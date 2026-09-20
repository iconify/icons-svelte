<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/silp9ount.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="silp9ount"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:globe-off" {...props}></Icon>
