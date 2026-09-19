<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6yx8db9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6yx8db9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:moon" {...props}></Icon>
