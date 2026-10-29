<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-lodmawc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-lodmawc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hand-solid" {...props}></Icon>
