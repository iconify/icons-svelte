<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywy6t0bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywy6t0bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-greater" {...props}></Icon>
