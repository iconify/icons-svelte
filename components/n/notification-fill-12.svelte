<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzqw2jbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xzqw2jbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:notification-fill-12" {...props}></Icon>
