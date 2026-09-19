<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whxvwgb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="whxvwgb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:caret-left" {...props}></Icon>
