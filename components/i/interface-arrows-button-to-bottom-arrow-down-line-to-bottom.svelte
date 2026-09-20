<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi28l3syr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bi28l3syr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-button-to-bottom-arrow-down-line-to-bottom" {...props}></Icon>
