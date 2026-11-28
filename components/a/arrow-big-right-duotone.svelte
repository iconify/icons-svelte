<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m47zqrbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m47zqrbmi primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-right-duotone" {...props}></Icon>
