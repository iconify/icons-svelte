<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku12kqght.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku12kqght"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:life-buoy-solid" {...props}></Icon>
