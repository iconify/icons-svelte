<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml1xv_bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml1xv_bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cube-fill" {...props}></Icon>
