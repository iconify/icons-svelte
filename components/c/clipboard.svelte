<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1hce7bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z1hce7bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:clipboard" {...props}></Icon>
