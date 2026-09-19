<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9vsy49dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9vsy49dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dashboard-square-remove" {...props}></Icon>
