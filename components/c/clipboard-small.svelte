<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9w0ejb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l9w0ejb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:clipboard-small" {...props}></Icon>
