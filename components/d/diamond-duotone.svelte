<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftozracwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftozracwo primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:diamond-duotone" {...props}></Icon>
