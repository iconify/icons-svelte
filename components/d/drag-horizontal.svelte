<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riynaeagy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riynaeagy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:drag-horizontal" {...props}></Icon>
