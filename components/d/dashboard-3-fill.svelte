<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb3of5z4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb3of5z4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dashboard-3-fill" {...props}></Icon>
