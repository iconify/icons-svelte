<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xretw0lyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xretw0lyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:crossed-fingers" {...props}></Icon>
