<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db9rc0bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="db9rc0bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:rev" {...props}></Icon>
