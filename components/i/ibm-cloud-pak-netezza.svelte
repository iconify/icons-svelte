<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufa-0g21i.css';
import '../../css/a/a_-4bw6-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ufa-0g21i"/><path class="a_-4bw6-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-pak-netezza" {...props}></Icon>
