<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6zmroqqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y6zmroqqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-item-align-bottom" {...props}></Icon>
