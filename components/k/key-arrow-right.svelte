<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfqcat_ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfqcat_ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:key-arrow-right" {...props}></Icon>
