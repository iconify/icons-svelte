<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so6g50bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so6g50bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drive-line" {...props}></Icon>
