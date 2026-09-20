<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sknjbp8wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sknjbp8wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:centos" {...props}></Icon>
