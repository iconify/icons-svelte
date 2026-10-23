<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-59flbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-59flbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bus-front" {...props}></Icon>
