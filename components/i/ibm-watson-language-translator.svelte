<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aesvwbb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aesvwbb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-language-translator" {...props}></Icon>
