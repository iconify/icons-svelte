<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5azz4pov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5azz4pov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lava-network" {...props}></Icon>
