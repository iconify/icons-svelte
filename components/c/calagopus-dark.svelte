<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdt2tgb-r.css';
import '../../css/o/o922f4zod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdt2tgb-r"/><path class="o922f4zod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calagopus-dark" {...props}></Icon>
