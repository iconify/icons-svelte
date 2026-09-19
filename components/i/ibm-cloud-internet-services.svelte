<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtp3hzbje.css';
import '../../css/t/tw9pjxlco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wtp3hzbje"/><path class="tw9pjxlco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-internet-services" {...props}></Icon>
