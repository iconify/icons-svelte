<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihzj57bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihzj57bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-grid-dots-filled" {...props}></Icon>
