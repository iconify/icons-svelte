<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfd7l7bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dfd7l7bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:link" {...props}></Icon>
