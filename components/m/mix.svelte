<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av8hnvbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="av8hnvbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mix" {...props}></Icon>
