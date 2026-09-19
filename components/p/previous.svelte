<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_x41mbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e_x41mbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:previous" {...props}></Icon>
