<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoac7cc0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uoac7cc0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:bug" {...props}></Icon>
