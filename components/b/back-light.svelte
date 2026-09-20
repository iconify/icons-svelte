<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwm128bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwm128bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:back-light" {...props}></Icon>
