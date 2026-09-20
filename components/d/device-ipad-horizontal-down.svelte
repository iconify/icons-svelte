<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-k_fzbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-k_fzbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-down" {...props}></Icon>
