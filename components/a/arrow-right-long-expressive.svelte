<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrh60-b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="jrh60-b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-right-long-expressive" {...props}></Icon>
