<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzprmcg0c.css';
import '../../css/o/otqm0acos.css';
import '../../css/o/oaa-h-w6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzprmcg0c"/><path class="otqm0acos"/><path class="oaa-h-w6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-vertical-bold-duotone" {...props}></Icon>
