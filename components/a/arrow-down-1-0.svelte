<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8gq40bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8gq40bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-1-0" {...props}></Icon>
