<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6sywuhsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j6sywuhsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:heading-1-paragraph-styles-heading-solid" {...props}></Icon>
