<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfga9qgse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bfga9qgse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-compress-vertical" {...props}></Icon>
