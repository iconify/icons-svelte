<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ampd2yblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ampd2yblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:equal-box" {...props}></Icon>
