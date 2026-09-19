<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy63rh4wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy63rh4wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:face-id" {...props}></Icon>
