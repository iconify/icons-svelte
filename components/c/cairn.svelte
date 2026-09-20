<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq4wpw7ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jq4wpw7ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cairn" {...props}></Icon>
