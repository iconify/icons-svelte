<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh7rg0bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh7rg0bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:codemirror" {...props}></Icon>
