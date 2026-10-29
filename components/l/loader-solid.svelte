<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdnluabmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdnluabmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:loader-solid" {...props}></Icon>
