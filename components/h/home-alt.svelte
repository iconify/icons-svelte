<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek9ttjrmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek9ttjrmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:home-alt" {...props}></Icon>
