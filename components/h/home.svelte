<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlxct7buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zlxct7buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:home" {...props}></Icon>
