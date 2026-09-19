<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-yolg93x.css';
import '../../css/x/x_6no5bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-yolg93x"/><path class="x_6no5bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:door-open" {...props}></Icon>
