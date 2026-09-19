<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqw--zbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqw--zbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:align-image-none" {...props}></Icon>
