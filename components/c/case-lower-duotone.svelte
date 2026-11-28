<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jelvk5ooi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jelvk5ooi primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:case-lower-duotone" {...props}></Icon>
