<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8ul3g7vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8ul3g7vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-3-square-bold" {...props}></Icon>
