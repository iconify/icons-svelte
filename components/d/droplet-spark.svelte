<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlg29yjew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlg29yjew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-spark" {...props}></Icon>
