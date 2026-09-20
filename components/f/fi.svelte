<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8ch-9riz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8ch-9riz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fi" {...props}></Icon>
