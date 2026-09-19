<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njoz_4bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njoz_4bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:events" {...props}></Icon>
