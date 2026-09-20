<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jav4t0bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jav4t0bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bed-double" {...props}></Icon>
