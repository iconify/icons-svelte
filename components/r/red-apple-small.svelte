<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db18-0-vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="db18-0-vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:red-apple-small" {...props}></Icon>
