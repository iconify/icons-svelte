<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br0osbb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br0osbb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-x-2" {...props}></Icon>
