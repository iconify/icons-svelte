<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez9qunc8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ez9qunc8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:align-top-two" {...props}></Icon>
