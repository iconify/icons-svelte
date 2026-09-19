<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz4cr67ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xz4cr67ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-text-to-speech" {...props}></Icon>
