<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4pdi5bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m4pdi5bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:egg" {...props}></Icon>
