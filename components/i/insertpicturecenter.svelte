<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8ipqhb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":960};
const content = `<path class="c8ipqhb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:insertpicturecenter" {...props}></Icon>
