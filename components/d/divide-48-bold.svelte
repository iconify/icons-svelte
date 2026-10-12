<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc42mqxbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fc42mqxbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:divide-48-bold" {...props}></Icon>
