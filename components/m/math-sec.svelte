<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr05tub9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr05tub9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-sec" {...props}></Icon>
