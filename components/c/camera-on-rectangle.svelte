<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sus55tbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="sus55tbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:camera-on-rectangle" {...props}></Icon>
