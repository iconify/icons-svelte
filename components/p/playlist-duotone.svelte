<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh9imabio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh9imabio primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:playlist-duotone" {...props}></Icon>
