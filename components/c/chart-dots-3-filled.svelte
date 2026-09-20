<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss7jp2b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7jp2b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-dots-3-filled" {...props}></Icon>
