<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuaxb_far.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yuaxb_far"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ankh" {...props}></Icon>
