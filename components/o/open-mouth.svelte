<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2sf9e_hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2sf9e_hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:open-mouth" {...props}></Icon>
