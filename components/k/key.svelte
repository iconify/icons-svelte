<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2gg3abuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2gg3abuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:key" {...props}></Icon>
