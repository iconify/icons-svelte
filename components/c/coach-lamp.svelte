<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o00-i8b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o00-i8b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coach-lamp" {...props}></Icon>
