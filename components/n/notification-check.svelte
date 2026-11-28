<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en9bmcc-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en9bmcc-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:notification-check" {...props}></Icon>
