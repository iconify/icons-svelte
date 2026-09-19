<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or7ddzi3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="or7ddzi3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:heavy-equals-sign" {...props}></Icon>
