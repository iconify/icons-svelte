<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5b2kyb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5b2kyb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:cancel" {...props}></Icon>
