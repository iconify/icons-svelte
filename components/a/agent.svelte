<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrorzdudt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lrorzdudt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:agent" {...props}></Icon>
