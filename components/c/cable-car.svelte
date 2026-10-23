<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syuj88pod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syuj88pod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cable-car" {...props}></Icon>
