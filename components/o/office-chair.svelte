<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z54yactek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z54yactek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:office-chair" {...props}></Icon>
