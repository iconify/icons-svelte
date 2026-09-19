<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eygaznwxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eygaznwxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hexagon-alt" {...props}></Icon>
