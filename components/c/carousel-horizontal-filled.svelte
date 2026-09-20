<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v32kf_bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v32kf_bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:carousel-horizontal-filled" {...props}></Icon>
