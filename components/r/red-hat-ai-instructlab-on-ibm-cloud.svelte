<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsxy61lui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nsxy61lui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:red-hat-ai-instructlab-on-ibm-cloud" {...props}></Icon>
