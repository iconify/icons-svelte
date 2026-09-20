<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geymjob6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geymjob6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:rating-star-ribbon-bold" {...props}></Icon>
