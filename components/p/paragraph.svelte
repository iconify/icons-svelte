<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt55xubhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wt55xubhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:paragraph" {...props}></Icon>
