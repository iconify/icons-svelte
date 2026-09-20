<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deptac1_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deptac1_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:broadcast-line" {...props}></Icon>
