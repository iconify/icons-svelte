<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/folet6ddy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="folet6ddy primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-double-up-duotone" {...props}></Icon>
