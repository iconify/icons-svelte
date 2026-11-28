<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb3alybyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb3alybyr primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heading-2-duotone" {...props}></Icon>
