<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtth0jbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtth0jbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-vertical" {...props}></Icon>
