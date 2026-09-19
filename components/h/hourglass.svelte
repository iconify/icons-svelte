<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eph_-e7pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="eph_-e7pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hourglass" {...props}></Icon>
