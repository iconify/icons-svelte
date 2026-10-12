<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td40zjb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td40zjb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:import-filled" {...props}></Icon>
