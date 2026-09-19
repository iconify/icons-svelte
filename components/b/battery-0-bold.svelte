<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv-jdh-qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yv-jdh-qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-0-bold" {...props}></Icon>
