<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niohfvb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="niohfvb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:embassy-10" {...props}></Icon>
