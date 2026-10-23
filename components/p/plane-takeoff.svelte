<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkgf-aboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkgf-aboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:plane-takeoff" {...props}></Icon>
