<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqqsoly8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="uqqsoly8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:mendeley" {...props}></Icon>
