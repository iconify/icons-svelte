<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s018ey81a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s018ey81a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bold" {...props}></Icon>
