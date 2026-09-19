<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys7-b_bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys7-b_bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-gitlab" {...props}></Icon>
