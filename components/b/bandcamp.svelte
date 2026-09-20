<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c91sfsbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c91sfsbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bandcamp" {...props}></Icon>
