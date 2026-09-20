<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2qy8rtqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2qy8rtqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:air-transat" {...props}></Icon>
