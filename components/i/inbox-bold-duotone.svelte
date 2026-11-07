<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6bs4k0fl.css';
import '../../css/y/yb3fr0bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6bs4k0fl"/><path class="yb3fr0bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-bold-duotone" {...props}></Icon>
