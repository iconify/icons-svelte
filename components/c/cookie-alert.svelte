<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f876vrb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f876vrb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cookie-alert" {...props}></Icon>
