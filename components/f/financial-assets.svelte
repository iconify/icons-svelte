<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2k3qxhyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n2k3qxhyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:financial-assets" {...props}></Icon>
