<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb8czbsnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vb8czbsnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-magnet" {...props}></Icon>
