<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s96df4b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s96df4b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location-thin" {...props}></Icon>
