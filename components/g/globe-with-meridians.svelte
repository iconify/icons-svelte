<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9gu4yi6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s9gu4yi6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:globe-with-meridians" {...props}></Icon>
