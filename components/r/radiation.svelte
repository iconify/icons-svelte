<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssy6g0bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssy6g0bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:radiation" {...props}></Icon>
