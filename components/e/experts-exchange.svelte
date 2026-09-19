<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdvsvtb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sdvsvtb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:experts-exchange" {...props}></Icon>
