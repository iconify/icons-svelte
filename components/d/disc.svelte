<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekjr1ib4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ekjr1ib4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:disc" {...props}></Icon>
