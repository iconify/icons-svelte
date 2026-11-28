<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cio6d1bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cio6d1bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:motorcycle-solid" {...props}></Icon>
