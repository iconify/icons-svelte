<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym6-ufb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym6-ufb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pill" {...props}></Icon>
