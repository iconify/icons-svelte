<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsakkgbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fsakkgbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-app" {...props}></Icon>
