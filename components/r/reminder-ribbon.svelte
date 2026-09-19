<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd4fdd5ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sd4fdd5ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:reminder-ribbon" {...props}></Icon>
