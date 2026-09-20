<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-rz6hkhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s-rz6hkhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:heading-1-paragraph-styles-heading-remix" {...props}></Icon>
