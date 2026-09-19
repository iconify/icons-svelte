<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgt6-fbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgt6-fbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:lightbulb-outline" {...props}></Icon>
