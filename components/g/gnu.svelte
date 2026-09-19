<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shu7q-blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="shu7q-blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gnu" {...props}></Icon>
