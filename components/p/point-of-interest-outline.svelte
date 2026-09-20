<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvpsj6bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvpsj6bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:point-of-interest-outline" {...props}></Icon>
