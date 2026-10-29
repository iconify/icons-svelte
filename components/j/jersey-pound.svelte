<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-lh599rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-lh599rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:jersey-pound" {...props}></Icon>
