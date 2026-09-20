<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1pltw_5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1pltw_5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-up-rectangle-filled" {...props}></Icon>
