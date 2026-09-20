<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey8tl5bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey8tl5bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:puzzle" {...props}></Icon>
