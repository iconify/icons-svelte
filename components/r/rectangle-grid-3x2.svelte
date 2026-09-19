<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k07n6zrtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="k07n6zrtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-grid-3x2" {...props}></Icon>
