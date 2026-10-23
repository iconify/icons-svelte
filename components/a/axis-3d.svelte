<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9vlz4hyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9vlz4hyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:axis-3d" {...props}></Icon>
