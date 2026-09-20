<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2wv2hb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s2wv2hb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:fuel-14" {...props}></Icon>
