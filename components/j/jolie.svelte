<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_qejgbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_qejgbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jolie" {...props}></Icon>
