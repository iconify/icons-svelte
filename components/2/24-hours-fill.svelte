<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qch9_uvyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qch9_uvyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:24-hours-fill" {...props}></Icon>
