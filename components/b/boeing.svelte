<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq5-61b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jq5-61b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:boeing" {...props}></Icon>
