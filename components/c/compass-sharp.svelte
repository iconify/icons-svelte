<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knmnij2dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knmnij2dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:compass-sharp" {...props}></Icon>
