<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvl7cvegy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvl7cvegy primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-right-down-left-duotone" {...props}></Icon>
