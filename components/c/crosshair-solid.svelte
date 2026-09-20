<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf5ppncjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf5ppncjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:crosshair-solid" {...props}></Icon>
