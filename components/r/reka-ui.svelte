<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlgo_mb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgo_mb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:reka-ui" {...props}></Icon>
