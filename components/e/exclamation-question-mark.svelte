<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwq5i-s2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mwq5i-s2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:exclamation-question-mark" {...props}></Icon>
