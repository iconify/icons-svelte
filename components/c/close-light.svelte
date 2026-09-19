<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzazltbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzazltbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-light" {...props}></Icon>
