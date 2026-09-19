<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekwir30sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekwir30sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:move-horizontal" {...props}></Icon>
