<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etgypeh5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="etgypeh5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:hinduist-14" {...props}></Icon>
