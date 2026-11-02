<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_pj-ub4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_pj-ub4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-circle-line" {...props}></Icon>
