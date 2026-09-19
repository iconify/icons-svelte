<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0k2oij5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0k2oij5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-1-thin" {...props}></Icon>
