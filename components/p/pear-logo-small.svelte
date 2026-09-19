<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfgqo6zaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yfgqo6zaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pear-logo-small" {...props}></Icon>
