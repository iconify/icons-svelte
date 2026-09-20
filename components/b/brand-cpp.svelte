<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2tq1fb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2tq1fb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-cpp" {...props}></Icon>
