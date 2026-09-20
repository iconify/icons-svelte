<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1wlilvok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1wlilvok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:group-3-fill" {...props}></Icon>
