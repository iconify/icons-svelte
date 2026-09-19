<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvlro3bdf.css';
import '../../css/w/whiyyb3wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvlro3bdf"/><path class="whiyyb3wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-pdf" {...props}></Icon>
