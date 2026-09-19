<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2k62cc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2k62cc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:lock-closed" {...props}></Icon>
