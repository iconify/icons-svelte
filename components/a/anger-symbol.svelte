<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd66ni5am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bd66ni5am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:anger-symbol" {...props}></Icon>
