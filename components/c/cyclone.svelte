<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b26h0iypd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b26h0iypd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cyclone" {...props}></Icon>
