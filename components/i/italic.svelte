<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6l2rnbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6l2rnbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:italic" {...props}></Icon>
