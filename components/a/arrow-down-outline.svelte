<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sslgg0brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sslgg0brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-down-outline" {...props}></Icon>
