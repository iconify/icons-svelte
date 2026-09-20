<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2m02b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eb2m02b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:caret-bottom" {...props}></Icon>
