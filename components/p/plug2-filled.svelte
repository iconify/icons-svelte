<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty5zirbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty5zirbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plug2-filled" {...props}></Icon>
