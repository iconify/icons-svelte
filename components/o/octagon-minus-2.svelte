<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noagkzbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noagkzbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-minus-2" {...props}></Icon>
