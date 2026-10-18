<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcbfky4-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcbfky4-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-full" {...props}></Icon>
