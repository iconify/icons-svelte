<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go64vgysl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="go64vgysl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:medical-symbol" {...props}></Icon>
