<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihz0fsb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ihz0fsb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:discharge-lounge" {...props}></Icon>
