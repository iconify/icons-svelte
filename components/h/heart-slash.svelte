<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re4ubykje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re4ubykje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heart-slash" {...props}></Icon>
