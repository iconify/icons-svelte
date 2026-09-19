<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqh-e-b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aqh-e-b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:card-index-dividers" {...props}></Icon>
