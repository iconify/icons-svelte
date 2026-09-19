<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1d3wbwag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v1d3wbwag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-ios" {...props}></Icon>
