<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6e5x5bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6e5x5bmc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-8-duotone" {...props}></Icon>
