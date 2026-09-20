<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym0uqj59a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ym0uqj59a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pdf-document" {...props}></Icon>
