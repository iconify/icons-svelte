<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1o7nwgpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1o7nwgpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heading-4" {...props}></Icon>
