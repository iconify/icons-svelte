<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldg0t_buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldg0t_buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-3-fill" {...props}></Icon>
