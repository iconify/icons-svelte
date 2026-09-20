<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv_bewyiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv_bewyiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-radius" {...props}></Icon>
