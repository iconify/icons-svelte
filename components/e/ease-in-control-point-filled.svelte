<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl1nelh_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl1nelh_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ease-in-control-point-filled" {...props}></Icon>
