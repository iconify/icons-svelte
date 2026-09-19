<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx4326jil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sx4326jil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:octopus" {...props}></Icon>
