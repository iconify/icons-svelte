<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8t4l7sis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w8t4l7sis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:heading-2-paragraph-styles-heading-solid" {...props}></Icon>
