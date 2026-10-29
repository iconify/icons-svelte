<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ygwptdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0ygwptdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:columns-3-solid" {...props}></Icon>
