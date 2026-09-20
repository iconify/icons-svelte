<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beoeifunj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beoeifunj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:map-direction" {...props}></Icon>
