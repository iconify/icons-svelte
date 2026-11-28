<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0syes_ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y0syes_ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-off-duotone" {...props}></Icon>
