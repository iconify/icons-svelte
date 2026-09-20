<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtb4bninq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wtb4bninq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nim" {...props}></Icon>
