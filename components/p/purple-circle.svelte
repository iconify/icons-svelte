<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spz3edb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="spz3edb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:purple-circle" {...props}></Icon>
