<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yifm1ubsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yifm1ubsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-back" {...props}></Icon>
