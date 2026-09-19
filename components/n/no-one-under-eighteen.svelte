<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s29yto5-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s29yto5-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:no-one-under-eighteen" {...props}></Icon>
