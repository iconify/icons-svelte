<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aar37xb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aar37xb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:monitor-smartphone" {...props}></Icon>
