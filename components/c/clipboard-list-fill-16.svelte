<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtt6g2roz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qtt6g2roz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-list-fill-16" {...props}></Icon>
