<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggzg1wb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggzg1wb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-z-a" {...props}></Icon>
