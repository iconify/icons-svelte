<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uabh9ub8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uabh9ub8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrows-crossing" {...props}></Icon>
