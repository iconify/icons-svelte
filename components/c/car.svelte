<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq1ylsxby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq1ylsxby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:car" {...props}></Icon>
