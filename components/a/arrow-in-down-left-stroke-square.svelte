<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu8duj-kd.css';
import '../../css/h/hcbbnl92k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu8duj-kd"/><path class="hcbbnl92k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-left-stroke-square" {...props}></Icon>
