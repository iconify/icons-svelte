<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu8duj-kd.css';
import '../../css/v/vxwbsu80r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu8duj-kd"/><path class="vxwbsu80r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-left-square-filled" {...props}></Icon>
