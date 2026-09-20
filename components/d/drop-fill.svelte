<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa1et4hnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1et4hnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drop-fill" {...props}></Icon>
