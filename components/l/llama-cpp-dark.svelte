<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpgij3bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cpgij3bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:llama-cpp-dark" {...props}></Icon>
