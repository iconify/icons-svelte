<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a660lgbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a660lgbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:justify-center" {...props}></Icon>
