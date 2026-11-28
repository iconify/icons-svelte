<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3-4bjboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3-4bjboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cast-x-solid" {...props}></Icon>
