<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-80zeltg.css';
import '../../css/w/w1a7x3uii.css';
import '../../css/w/w-y6bqe0z.css';
import '../../css/k/k5t9_hi4j.css';
import '../../css/h/hvsizj-rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-80zeltg wm-shadow"/><path class="w1a7x3uii wm-k"/><path class="w-y6bqe0z wm-k"/><path class="k5t9_hi4j wm-s"/><path class="hvsizj-rr wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:repeat-1" {...props}></Icon>
