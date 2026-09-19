<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q26m2lrpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q26m2lrpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:download" {...props}></Icon>
