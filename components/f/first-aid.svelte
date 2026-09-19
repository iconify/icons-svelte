<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv_cacb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv_cacb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:first-aid" {...props}></Icon>
