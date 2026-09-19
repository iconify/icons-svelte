<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiky2nbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kiky2nbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nlc2" {...props}></Icon>
