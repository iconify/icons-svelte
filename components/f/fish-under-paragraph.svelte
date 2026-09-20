<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eey-7uxwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eey-7uxwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-under-paragraph" {...props}></Icon>
