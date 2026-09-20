<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_rcp1bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_rcp1bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-3d-filled" {...props}></Icon>
