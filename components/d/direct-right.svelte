<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whrvgkbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whrvgkbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:direct-right" {...props}></Icon>
