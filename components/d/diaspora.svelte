<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wln7cnp3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wln7cnp3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:diaspora" {...props}></Icon>
