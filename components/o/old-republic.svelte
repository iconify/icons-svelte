<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qijeockla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qijeockla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:old-republic" {...props}></Icon>
