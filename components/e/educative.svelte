<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx2s7_b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx2s7_b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:educative" {...props}></Icon>
