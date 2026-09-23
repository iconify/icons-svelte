<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcke1qbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcke1qbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:option-duotone" {...props}></Icon>
