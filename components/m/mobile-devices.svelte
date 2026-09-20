<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbqaj9bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jbqaj9bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:mobile-devices" {...props}></Icon>
