<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szawn9-ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="szawn9-ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:remix" {...props}></Icon>
