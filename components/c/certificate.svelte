<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk9vvrbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yk9vvrbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:certificate" {...props}></Icon>
