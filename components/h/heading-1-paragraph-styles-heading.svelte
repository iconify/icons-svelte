<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qie5wsm-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qie5wsm-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:heading-1-paragraph-styles-heading" {...props}></Icon>
