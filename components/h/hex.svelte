<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shu57bcsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="shu57bcsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hex" {...props}></Icon>
