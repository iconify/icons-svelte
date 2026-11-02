<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya-2g1bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya-2g1bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:droplets-line" {...props}></Icon>
