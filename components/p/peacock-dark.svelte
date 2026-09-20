<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx18n3bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx18n3bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peacock-dark" {...props}></Icon>
