<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ropi4qb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ropi4qb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-medium" {...props}></Icon>
