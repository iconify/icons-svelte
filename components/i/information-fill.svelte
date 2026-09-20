<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s02i13bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s02i13bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:information-fill" {...props}></Icon>
