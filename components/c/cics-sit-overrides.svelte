<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbvsrd_3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lbvsrd_3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-sit-overrides" {...props}></Icon>
