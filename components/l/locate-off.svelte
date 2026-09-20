<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s053iybax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s053iybax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:locate-off" {...props}></Icon>
