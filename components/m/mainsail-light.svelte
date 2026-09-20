<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8ksa1bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8ksa1bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mainsail-light" {...props}></Icon>
