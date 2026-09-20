<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-728ubyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-728ubyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:bucket" {...props}></Icon>
