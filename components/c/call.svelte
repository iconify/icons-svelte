<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm-3lhb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rm-3lhb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:call" {...props}></Icon>
