<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lztr7todt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lztr7todt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:airplane-alt-02" {...props}></Icon>
