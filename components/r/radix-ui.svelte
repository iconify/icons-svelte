<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trv0p2amd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trv0p2amd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:radix-ui" {...props}></Icon>
