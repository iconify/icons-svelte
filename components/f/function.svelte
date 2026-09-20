<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4xqxgbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j4xqxgbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:function" {...props}></Icon>
