<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7x8mh8gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7x8mh8gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:move-solid" {...props}></Icon>
