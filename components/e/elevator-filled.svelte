<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smnhnb-ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smnhnb-ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:elevator-filled" {...props}></Icon>
