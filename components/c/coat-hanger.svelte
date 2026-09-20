<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu66jk8uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu66jk8uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:coat-hanger" {...props}></Icon>
