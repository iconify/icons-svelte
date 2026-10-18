<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sguv65_5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sguv65_5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:crown" {...props}></Icon>
