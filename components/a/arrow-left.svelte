<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjdv0xboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":380,"height":790};
const content = `<path class="qjdv0xboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:arrow-left" {...props}></Icon>
