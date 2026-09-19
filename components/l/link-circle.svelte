<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-1rciyzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x-1rciyzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:link-circle" {...props}></Icon>
