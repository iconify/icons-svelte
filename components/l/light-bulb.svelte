<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwmy-8bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gwmy-8bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:light-bulb" {...props}></Icon>
