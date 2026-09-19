<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4n6sib-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f4n6sib-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:campsite" {...props}></Icon>
