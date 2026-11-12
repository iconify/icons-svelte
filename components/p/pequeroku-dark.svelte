<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccmhyqbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ccmhyqbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pequeroku-dark" {...props}></Icon>
