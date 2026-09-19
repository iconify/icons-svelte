<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6bg4tb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6bg4tb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe" {...props}></Icon>
