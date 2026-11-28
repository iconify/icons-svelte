<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i76gii7ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i76gii7ve primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:brackets-duotone" {...props}></Icon>
