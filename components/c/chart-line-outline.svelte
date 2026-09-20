<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj7w25rnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj7w25rnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:chart-line-outline" {...props}></Icon>
