<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upo8e8zvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="upo8e8zvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:america" {...props}></Icon>
