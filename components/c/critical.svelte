<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geqa0016h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geqa0016h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:critical" {...props}></Icon>
