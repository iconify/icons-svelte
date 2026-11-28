<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8qti5b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8qti5b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:close-solid" {...props}></Icon>
