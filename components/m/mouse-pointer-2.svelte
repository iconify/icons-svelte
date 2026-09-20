<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtxprhl3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtxprhl3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouse-pointer-2" {...props}></Icon>
