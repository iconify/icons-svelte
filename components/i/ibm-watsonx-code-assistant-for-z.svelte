<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzk7dyusq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gzk7dyusq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watsonx-code-assistant-for-z" {...props}></Icon>
