<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0nks7b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0nks7b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bus-solid" {...props}></Icon>
