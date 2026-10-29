<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsdz_cbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsdz_cbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-solid" {...props}></Icon>
