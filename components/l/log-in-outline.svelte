<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gco9hqb4k.css';
import '../../css/o/ovur34-xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gco9hqb4k"/><path class="ovur34-xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:log-in-outline" {...props}></Icon>
