<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv8o2pb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sv8o2pb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:micro-blog" {...props}></Icon>
