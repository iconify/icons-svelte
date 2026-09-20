<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl6g3-bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl6g3-bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ease-in-out-control-points" {...props}></Icon>
