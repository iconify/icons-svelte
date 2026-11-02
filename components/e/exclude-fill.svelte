<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7s7dcjej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7s7dcjej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exclude-fill" {...props}></Icon>
