<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/modq4lqgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="modq4lqgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:classical-building" {...props}></Icon>
