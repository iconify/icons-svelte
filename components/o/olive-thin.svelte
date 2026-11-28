<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksj6wuf6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ksj6wuf6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:olive-thin" {...props}></Icon>
