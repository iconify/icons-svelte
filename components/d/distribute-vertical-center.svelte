<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua3rgubbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua3rgubbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:distribute-vertical-center" {...props}></Icon>
