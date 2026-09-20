<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltoq1dbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltoq1dbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-open-source-filled" {...props}></Icon>
