<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyq_t3ubt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyq_t3ubt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:appsignal" {...props}></Icon>
