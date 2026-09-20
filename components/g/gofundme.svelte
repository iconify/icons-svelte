<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z86ay1b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z86ay1b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gofundme" {...props}></Icon>
