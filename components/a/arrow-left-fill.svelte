<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg_scyb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg_scyb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-fill" {...props}></Icon>
