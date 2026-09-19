<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7gm_zboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q7gm_zboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:heart" {...props}></Icon>
