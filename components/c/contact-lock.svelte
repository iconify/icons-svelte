<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmswr3_ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pmswr3_ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:contact-lock" {...props}></Icon>
