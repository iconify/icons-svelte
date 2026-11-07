<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1j0ccckq.css';
import '../../css/b/bdli7f47j.css';
import '../../css/x/xe1ahotxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1j0ccckq"/><path class="bdli7f47j"/><path class="xe1ahotxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-bold-duotone" {...props}></Icon>
