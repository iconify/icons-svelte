<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1zepsbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j1zepsbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:minus" {...props}></Icon>
