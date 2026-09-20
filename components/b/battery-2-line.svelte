<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sim1-4btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sim1-4btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:battery-2-line" {...props}></Icon>
