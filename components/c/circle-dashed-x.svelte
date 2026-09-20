<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szz_hddff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szz_hddff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-x" {...props}></Icon>
