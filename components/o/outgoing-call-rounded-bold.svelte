<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4_4mjb9l.css';
import '../../css/a/a8539c-uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4_4mjb9l"/><path class="a8539c-uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:outgoing-call-rounded-bold" {...props}></Icon>
