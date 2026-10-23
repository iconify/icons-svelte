<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k19hxw-al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k19hxw-al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-check-2" {...props}></Icon>
