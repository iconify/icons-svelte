<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6j2utb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6j2utb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-left-l" {...props}></Icon>
