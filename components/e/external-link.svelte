<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da27cu_vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da27cu_vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:external-link" {...props}></Icon>
