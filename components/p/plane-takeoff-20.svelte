<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui-3y7kiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ui-3y7kiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plane-takeoff-20" {...props}></Icon>
