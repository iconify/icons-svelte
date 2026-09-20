<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_-4ib5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="pv_-4ib5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:record" {...props}></Icon>
