<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfjl1qd8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="sfjl1qd8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fedora" {...props}></Icon>
