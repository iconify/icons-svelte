<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad2pn_1bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ad2pn_1bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-software-watsonx-data-structured-import" {...props}></Icon>
