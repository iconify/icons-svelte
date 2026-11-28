<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9oef4b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q9oef4b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-json-light" {...props}></Icon>
