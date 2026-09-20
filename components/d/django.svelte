<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-wdiqbjd.css';
import '../../css/i/it2p9rrcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t-wdiqbjd"/><path class="it2p9rrcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:django" {...props}></Icon>
