<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itkxm1eaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itkxm1eaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-exit-fullscreen" {...props}></Icon>
