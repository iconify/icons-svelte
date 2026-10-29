<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogh3b21vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogh3b21vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-down-to-line-solid" {...props}></Icon>
