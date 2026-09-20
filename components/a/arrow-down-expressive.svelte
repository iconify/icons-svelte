<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t40y_0hxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t40y_0hxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-down-expressive" {...props}></Icon>
